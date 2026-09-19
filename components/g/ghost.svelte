<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy55s8bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zy55s8bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ghost" {...props}></Icon>
