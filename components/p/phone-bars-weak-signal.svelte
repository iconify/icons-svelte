<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft2odlb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ft2odlb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-bars-weak-signal" {...props}></Icon>
