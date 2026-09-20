<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iave49bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iave49bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pint-glass" {...props}></Icon>
