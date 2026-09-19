<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjkafkbvo.css';
import '../../css/b/b6ueueufz.css';
import '../../css/n/nrqcwibjb.css';
import '../../css/e/emew_ipme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qjkafkbvo"/><circle class="b6ueueufz"/><path class="nrqcwibjb"/><path class="emew_ipme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:global-loan-and-trial" {...props}></Icon>
