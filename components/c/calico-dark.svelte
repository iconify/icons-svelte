<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhwetz1ra.css';
import '../../css/e/ep2grliyt.css';
import '../../css/t/t1d4nlbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhwetz1ra"/><path class="ep2grliyt"/><path class="t1d4nlbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calico-dark" {...props}></Icon>
