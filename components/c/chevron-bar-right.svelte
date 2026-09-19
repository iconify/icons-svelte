<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld5of7bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ld5of7bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-bar-right" {...props}></Icon>
