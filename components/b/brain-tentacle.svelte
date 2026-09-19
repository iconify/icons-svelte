<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zziq5zbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zziq5zbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brain-tentacle" {...props}></Icon>
