<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngnx30bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ngnx30bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-down-circle-fill" {...props}></Icon>
