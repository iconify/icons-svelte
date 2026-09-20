<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7f8lidrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f8lidrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:album-solid" {...props}></Icon>
