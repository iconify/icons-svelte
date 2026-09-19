<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7gtf23ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="p7gtf23ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:infinity-2" {...props}></Icon>
