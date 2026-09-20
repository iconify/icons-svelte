<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umgw0flwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umgw0flwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-history-fill" {...props}></Icon>
