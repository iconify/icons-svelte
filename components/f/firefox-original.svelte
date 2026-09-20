<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhin5jgof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jhin5jgof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:firefox-original" {...props}></Icon>
