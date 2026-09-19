<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj-wy4bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj-wy4bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:forearm" {...props}></Icon>
