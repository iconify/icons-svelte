<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv_c7cbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv_c7cbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:distress-signal" {...props}></Icon>
