<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qps999guh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qps999guh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bold-stroke-12" {...props}></Icon>
