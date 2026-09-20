<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhv95j8ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhv95j8ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-lightbulb-outline" {...props}></Icon>
