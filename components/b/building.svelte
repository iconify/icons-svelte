<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtfo2gk7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="dtfo2gk7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:building" {...props}></Icon>
