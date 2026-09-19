<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-i5cov4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-i5cov4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pistol-gun" {...props}></Icon>
