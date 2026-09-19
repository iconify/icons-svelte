<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cytyfkvmo.css';
import '../../css/y/y2gcv4obb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cytyfkvmo"/><path class="y2gcv4obb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-ltr-fill-12" {...props}></Icon>
