<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk29gcbsq.css';
import '../../css/k/ktus5xkah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qk29gcbsq"/><path clip-rule="evenodd" class="ktus5xkah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pdf-solid" {...props}></Icon>
