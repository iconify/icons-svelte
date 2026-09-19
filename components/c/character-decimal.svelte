<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r86rvjbis.css';
import '../../css/b/b-hc40bpi.css';
import '../../css/z/zlrqd59ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r86rvjbis"/><path class="b-hc40bpi"/><path class="zlrqd59ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-decimal" {...props}></Icon>
