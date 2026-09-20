<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek6t0acuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek6t0acuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:incognito-circle-off" {...props}></Icon>
