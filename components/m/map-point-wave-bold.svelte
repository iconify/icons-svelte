<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzflwis8e.css';
import '../../css/a/a-jc6dbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzflwis8e"/><path clip-rule="evenodd" class="a-jc6dbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-wave-bold" {...props}></Icon>
