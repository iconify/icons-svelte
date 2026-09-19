<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq_uh0yba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bq_uh0yba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crystalize" {...props}></Icon>
