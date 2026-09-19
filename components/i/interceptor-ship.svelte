<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e82dw-bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e82dw-bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:interceptor-ship" {...props}></Icon>
