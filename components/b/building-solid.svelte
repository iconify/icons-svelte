<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntg47rbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntg47rbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-solid" {...props}></Icon>
