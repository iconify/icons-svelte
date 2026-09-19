<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0oaufjyz.css';
import '../../css/t/t3d4-stmx.css';
import '../../css/p/p8i175dpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0oaufjyz"/><path class="t3d4-stmx"/><path class="p8i175dpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pinkwallet" {...props}></Icon>
