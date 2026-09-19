<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs_25ysim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gs_25ysim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-dollar" {...props}></Icon>
