<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtma7g7nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtma7g7nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-x-sharp" {...props}></Icon>
