<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f11294w7f.css';
import '../../css/c/c6vxn_-6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f11294w7f"/><path class="c6vxn_-6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dashboard-reference" {...props}></Icon>
