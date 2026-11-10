<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsiwf9b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dsiwf9b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:center" {...props}></Icon>
