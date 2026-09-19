<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yen3ajh1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yen3ajh1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:program-action" {...props}></Icon>
