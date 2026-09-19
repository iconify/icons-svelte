<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nveg2nboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="nveg2nboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:ghost" {...props}></Icon>
