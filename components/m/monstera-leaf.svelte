<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96_q3ijz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h96_q3ijz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:monstera-leaf" {...props}></Icon>
