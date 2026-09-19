<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huue4xb4c.css';
import '../../css/o/o6fdclsme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="huue4xb4c"/><path class="o6fdclsme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pie-chart" {...props}></Icon>
