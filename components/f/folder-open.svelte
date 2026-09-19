<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3humqbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="n3humqbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:folder-open" {...props}></Icon>
