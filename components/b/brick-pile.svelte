<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbnfk85vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbnfk85vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brick-pile" {...props}></Icon>
