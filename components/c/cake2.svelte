<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcf7zrb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rcf7zrb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cake2" {...props}></Icon>
