<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyzwm3lxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyzwm3lxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:compare-light" {...props}></Icon>
