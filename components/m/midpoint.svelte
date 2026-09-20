<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsky6xb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="vsky6xb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:midpoint" {...props}></Icon>
