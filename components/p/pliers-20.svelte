<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6cl-bwp.css';
import '../../css/x/xollm1waj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dg6cl-bwp"/><path class="xollm1waj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pliers-20" {...props}></Icon>
