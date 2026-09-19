<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjls1k5-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjls1k5-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-dissipation" {...props}></Icon>
