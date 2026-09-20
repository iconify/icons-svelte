<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls11p80_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls11p80_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:replay" {...props}></Icon>
