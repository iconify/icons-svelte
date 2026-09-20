<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmw_3pbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gmw_3pbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chip-bag-with-chip" {...props}></Icon>
