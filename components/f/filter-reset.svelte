<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uszyinm-l.css';
import '../../css/e/evom4wbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uszyinm-l"/><path class="evom4wbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:filter-reset" {...props}></Icon>
