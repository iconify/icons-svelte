<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt3uzf15z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qt3uzf15z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pills" {...props}></Icon>
