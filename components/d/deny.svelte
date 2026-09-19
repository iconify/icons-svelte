<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpx6p7ooe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rpx6p7ooe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:deny" {...props}></Icon>
