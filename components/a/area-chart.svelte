<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkxa0gb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dkxa0gb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:area-chart" {...props}></Icon>
