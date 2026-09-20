<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktf322itg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktf322itg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-text" {...props}></Icon>
