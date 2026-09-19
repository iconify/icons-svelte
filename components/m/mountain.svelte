<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6blx7bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="k6blx7bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mountain" {...props}></Icon>
