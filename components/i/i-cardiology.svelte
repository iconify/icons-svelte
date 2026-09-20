<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms1ycbcfl.css';
import '../../css/l/ln5q-fheg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ms1ycbcfl"/><path class="ln5q-fheg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-cardiology" {...props}></Icon>
