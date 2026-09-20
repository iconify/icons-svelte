<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8-7bccmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m8-7bccmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:confused-face-in-circle" {...props}></Icon>
