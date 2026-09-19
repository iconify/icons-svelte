<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxepg49nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxepg49nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chest" {...props}></Icon>
