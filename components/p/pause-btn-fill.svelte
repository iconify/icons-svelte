<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r69m7kc5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r69m7kc5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pause-btn-fill" {...props}></Icon>
