<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6hahgbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x6hahgbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dotlist" {...props}></Icon>
