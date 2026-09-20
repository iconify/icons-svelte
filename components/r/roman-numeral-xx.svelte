<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifk465b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ifk465b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-xx" {...props}></Icon>
