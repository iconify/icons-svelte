<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_m6s_8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_m6s_8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brain-freeze" {...props}></Icon>
