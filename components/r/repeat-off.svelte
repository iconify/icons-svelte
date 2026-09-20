<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhpt4fbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhpt4fbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:repeat-off" {...props}></Icon>
