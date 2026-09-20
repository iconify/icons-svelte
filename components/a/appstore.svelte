<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-ub77t1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-ub77t1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:appstore" {...props}></Icon>
