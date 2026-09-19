<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4akjb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf4akjb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:raspberry" {...props}></Icon>
