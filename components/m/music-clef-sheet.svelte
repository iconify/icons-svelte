<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j---shb0m.css';
import '../../css/n/neea8pi3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j---shb0m"/><path class="neea8pi3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-clef-sheet" {...props}></Icon>
