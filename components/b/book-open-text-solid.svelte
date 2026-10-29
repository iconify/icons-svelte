<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-mvzwbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-mvzwbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-text-solid" {...props}></Icon>
