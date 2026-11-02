<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juu2knbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juu2knbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:escalator-down-line" {...props}></Icon>
