<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kald8wfhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kald8wfhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-transfer-stroke-12" {...props}></Icon>
