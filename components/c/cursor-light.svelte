<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjdgb_tlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":466.73,"height":532.09};
const content = `<path class="qjdgb_tlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cursor-light" {...props}></Icon>
