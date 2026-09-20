<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t95rl8bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t95rl8bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-outline" {...props}></Icon>
