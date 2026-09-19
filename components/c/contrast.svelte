<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljt949bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ljt949bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:contrast" {...props}></Icon>
