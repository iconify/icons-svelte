<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2s7v_ssu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2s7v_ssu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:minus-box-outline" {...props}></Icon>
