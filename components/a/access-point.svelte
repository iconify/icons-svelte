<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz_0v_mxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz_0v_mxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:access-point" {...props}></Icon>
