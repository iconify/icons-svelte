<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6d7q2bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6d7q2bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-exclamation" {...props}></Icon>
