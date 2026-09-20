<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh-ubxb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lh-ubxb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-xi" {...props}></Icon>
