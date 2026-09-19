<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvslmzb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvslmzb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bok-choy" {...props}></Icon>
