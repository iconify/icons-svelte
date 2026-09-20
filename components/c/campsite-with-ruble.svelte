<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx0bnjbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rx0bnjbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-ruble" {...props}></Icon>
