<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/artxnr_oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="artxnr_oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mason-jar" {...props}></Icon>
