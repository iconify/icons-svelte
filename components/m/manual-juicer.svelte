<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpeemlbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vpeemlbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:manual-juicer" {...props}></Icon>
