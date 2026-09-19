<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js_s7u-5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":77,"height":649};
const content = `<path class="js_s7u-5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:colon" {...props}></Icon>
