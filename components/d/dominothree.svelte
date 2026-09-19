<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf4c-9c0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="zf4c-9c0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominothree" {...props}></Icon>
