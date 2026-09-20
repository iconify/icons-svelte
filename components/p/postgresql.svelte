<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqkpc9b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqkpc9b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:postgresql" {...props}></Icon>
