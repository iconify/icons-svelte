<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuebe5bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iuebe5bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pawprint" {...props}></Icon>
