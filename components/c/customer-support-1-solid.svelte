<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y67-rrfds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y67-rrfds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:customer-support-1-solid" {...props}></Icon>
