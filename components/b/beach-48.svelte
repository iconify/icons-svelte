<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxy5wbcie.css';
import '../../css/c/clh0ambgx.css';
import '../../css/w/wfx3nk7mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oxy5wbcie"/><path class="clh0ambgx"/><path class="wfx3nk7mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beach-48" {...props}></Icon>
