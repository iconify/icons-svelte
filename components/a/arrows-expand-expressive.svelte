<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrjwoobuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjwoobuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrows-expand-expressive" {...props}></Icon>
