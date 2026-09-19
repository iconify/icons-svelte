<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo7_onhnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yo7_onhnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-transfer-fill-12" {...props}></Icon>
