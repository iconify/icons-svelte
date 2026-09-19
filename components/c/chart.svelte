<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onbnr902k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="onbnr902k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chart" {...props}></Icon>
