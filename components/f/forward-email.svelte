<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh2xd8hhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh2xd8hhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:forward-email" {...props}></Icon>
