<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3hk2vf-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="z3hk2vf-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-down" {...props}></Icon>
