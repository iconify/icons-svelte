<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hszia39-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="hszia39-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:id-badge" {...props}></Icon>
