<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_2q7uzrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c_2q7uzrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:quote-bubble-fill" {...props}></Icon>
