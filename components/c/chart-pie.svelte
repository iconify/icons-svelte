<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8goq-vxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d8goq-vxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-pie" {...props}></Icon>
