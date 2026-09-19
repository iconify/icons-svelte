<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/carkr5bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="carkr5bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:elephant" {...props}></Icon>
