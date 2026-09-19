<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c680_fk7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c680_fk7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pool-triangle" {...props}></Icon>
