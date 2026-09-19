<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_w85bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lh_w85bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meeple-army" {...props}></Icon>
