<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9z5hbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="in9z5hbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mail" {...props}></Icon>
