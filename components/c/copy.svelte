<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_c48qb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":496};
const content = `<path class="h_c48qb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:copy" {...props}></Icon>
