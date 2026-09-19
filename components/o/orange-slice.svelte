<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdt1xv_kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdt1xv_kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:orange-slice" {...props}></Icon>
