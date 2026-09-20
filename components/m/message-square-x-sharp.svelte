<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob86dxngx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob86dxngx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-x-sharp" {...props}></Icon>
