<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tszlukbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tszlukbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-drop-circle-outline" {...props}></Icon>
