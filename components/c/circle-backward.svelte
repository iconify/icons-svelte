<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak00kswdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ak00kswdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-backward" {...props}></Icon>
