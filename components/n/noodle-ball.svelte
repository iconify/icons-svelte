<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clzusyb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clzusyb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:noodle-ball" {...props}></Icon>
