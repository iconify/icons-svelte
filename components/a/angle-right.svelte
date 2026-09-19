<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex-j_h13o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="ex-j_h13o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-right" {...props}></Icon>
