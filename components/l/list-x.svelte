<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlgm-dd3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlgm-dd3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-x" {...props}></Icon>
