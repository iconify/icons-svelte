<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk2ph2lxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="dk2ph2lxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pet-carrier" {...props}></Icon>
