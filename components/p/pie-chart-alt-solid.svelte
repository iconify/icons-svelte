<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueaxwlb4u.css';
import '../../css/f/fosgzfbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ueaxwlb4u"/><path class="fosgzfbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pie-chart-alt-solid" {...props}></Icon>
