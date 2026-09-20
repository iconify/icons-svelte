<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8eq4u5hf.css';
import '../../css/m/mabwzbbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8eq4u5hf"/><path class="mabwzbbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:check-circle" {...props}></Icon>
