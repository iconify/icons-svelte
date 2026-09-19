<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhuhh32fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bhuhh32fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:person-public" {...props}></Icon>
