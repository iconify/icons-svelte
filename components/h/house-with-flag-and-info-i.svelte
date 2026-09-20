<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw51fnti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkw51fnti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:house-with-flag-and-info-i" {...props}></Icon>
