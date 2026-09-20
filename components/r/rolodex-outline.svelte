<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfyj_sbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfyj_sbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rolodex-outline" {...props}></Icon>
