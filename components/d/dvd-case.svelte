<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx7je-blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tx7je-blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dvd-case" {...props}></Icon>
