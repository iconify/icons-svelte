<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne6g2k11l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ne6g2k11l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mechanic-garage" {...props}></Icon>
