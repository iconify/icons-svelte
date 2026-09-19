<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbqcy-x8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kbqcy-x8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:rainbow" {...props}></Icon>
