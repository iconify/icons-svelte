<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shvlg_s5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="shvlg_s5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:person" {...props}></Icon>
