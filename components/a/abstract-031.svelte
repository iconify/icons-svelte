<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqohbbb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqohbbb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-031" {...props}></Icon>
