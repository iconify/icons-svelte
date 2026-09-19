<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt4e19b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gt4e19b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:i-r-m-forward" {...props}></Icon>
