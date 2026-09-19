<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mns0wob5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mns0wob5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bolter-gun" {...props}></Icon>
