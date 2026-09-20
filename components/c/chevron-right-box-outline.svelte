<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr5k80rzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr5k80rzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-right-box-outline" {...props}></Icon>
