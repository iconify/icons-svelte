<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaee0nbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eaee0nbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dwarf-king" {...props}></Icon>
