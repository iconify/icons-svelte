<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0nxy1bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0nxy1bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-wave" {...props}></Icon>
