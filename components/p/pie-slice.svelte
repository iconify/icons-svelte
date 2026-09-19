<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byzxr3b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byzxr3b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pie-slice" {...props}></Icon>
