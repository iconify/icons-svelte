<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uridjib7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uridjib7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-from-line" {...props}></Icon>
