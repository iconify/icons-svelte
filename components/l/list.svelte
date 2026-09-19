<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7w05_3ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7w05_3ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:list" {...props}></Icon>
