<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzwz2vbkt.css';
import '../../css/r/rf258g3jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tzwz2vbkt"/><path class="rf258g3jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:discount" {...props}></Icon>
