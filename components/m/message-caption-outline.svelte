<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6aq9l9vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6aq9l9vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:message-caption-outline" {...props}></Icon>
