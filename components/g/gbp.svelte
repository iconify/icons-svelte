<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg_-8gbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jg_-8gbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:gbp" {...props}></Icon>
