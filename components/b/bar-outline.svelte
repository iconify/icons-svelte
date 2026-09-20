<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utgo1x16x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utgo1x16x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bar-outline" {...props}></Icon>
