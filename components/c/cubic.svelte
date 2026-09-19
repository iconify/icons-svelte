<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaaad0bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="uaaad0bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cubic" {...props}></Icon>
