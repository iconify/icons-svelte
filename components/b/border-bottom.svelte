<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk2-5tbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk2-5tbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-bottom" {...props}></Icon>
