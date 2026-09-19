<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz6fzlwom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tz6fzlwom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-point-down" {...props}></Icon>
