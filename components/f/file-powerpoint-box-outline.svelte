<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzghf5blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzghf5blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-powerpoint-box-outline" {...props}></Icon>
