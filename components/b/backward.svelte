<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9lr3pbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9lr3pbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:backward" {...props}></Icon>
