<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvaknskke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="dvaknskke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:8" {...props}></Icon>
