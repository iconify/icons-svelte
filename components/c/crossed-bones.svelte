<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_fdr6xmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_fdr6xmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-bones" {...props}></Icon>
