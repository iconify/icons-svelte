<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqrex6h4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xqrex6h4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:backward" {...props}></Icon>
