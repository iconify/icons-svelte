<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qib8-s6ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qib8-s6ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bagel" {...props}></Icon>
