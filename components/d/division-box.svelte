<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkhg6134t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkhg6134t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:division-box" {...props}></Icon>
