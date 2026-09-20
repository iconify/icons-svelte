<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plqf3fb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plqf3fb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:markdown-outline" {...props}></Icon>
