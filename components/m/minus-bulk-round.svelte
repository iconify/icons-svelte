<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evubeznvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evubeznvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:minus-bulk-round" {...props}></Icon>
