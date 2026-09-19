<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrv_jrbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrv_jrbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:megaphone" {...props}></Icon>
