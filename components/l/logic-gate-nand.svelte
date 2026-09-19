<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqjlsoc3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zqjlsoc3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-nand" {...props}></Icon>
