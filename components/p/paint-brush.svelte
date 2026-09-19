<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kohcfm9fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kohcfm9fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paint-brush" {...props}></Icon>
