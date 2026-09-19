<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zog80tfii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zog80tfii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:door" {...props}></Icon>
