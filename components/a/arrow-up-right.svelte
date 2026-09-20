<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydjka0b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydjka0b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-right" {...props}></Icon>
