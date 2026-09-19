<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbo93mi9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbo93mi9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-023" {...props}></Icon>
