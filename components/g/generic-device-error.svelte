<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-vuseb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-vuseb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-error" {...props}></Icon>
