<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0_hr98mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p0_hr98mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-sm-fill-12" {...props}></Icon>
