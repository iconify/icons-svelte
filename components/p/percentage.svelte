<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unf88w3zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unf88w3zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage" {...props}></Icon>
