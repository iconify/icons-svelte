<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx0i85btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mx0i85btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:copy-stroke-20" {...props}></Icon>
