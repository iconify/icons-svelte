<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ksycc_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4ksycc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:light-helm" {...props}></Icon>
