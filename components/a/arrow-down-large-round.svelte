<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhxdvy5ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxdvy5ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-large-round" {...props}></Icon>
