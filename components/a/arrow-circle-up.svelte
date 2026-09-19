<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0n8kqbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0n8kqbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-circle-up" {...props}></Icon>
