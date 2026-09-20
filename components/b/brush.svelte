<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfc93_bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfc93_bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brush" {...props}></Icon>
