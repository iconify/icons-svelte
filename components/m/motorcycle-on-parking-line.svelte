<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0exovbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l0exovbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-on-parking-line" {...props}></Icon>
