<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awzd49bdq.css';
import '../../css/q/qmjsi1lav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="awzd49bdq"/><path class="qmjsi1lav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:crown" {...props}></Icon>
