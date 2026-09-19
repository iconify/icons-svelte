<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8gm18wil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p8gm18wil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:previous" {...props}></Icon>
