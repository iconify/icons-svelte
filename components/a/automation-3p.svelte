<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8k-0xb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n8k-0xb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:automation-3p" {...props}></Icon>
