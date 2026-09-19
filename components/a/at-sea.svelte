<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg6l1rb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hg6l1rb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:at-sea" {...props}></Icon>
