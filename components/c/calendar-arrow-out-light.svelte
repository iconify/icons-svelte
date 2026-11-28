<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfraj543k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qfraj543k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-out-light" {...props}></Icon>
