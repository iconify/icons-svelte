<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm1-5mbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qm1-5mbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:cloud-weather" {...props}></Icon>
