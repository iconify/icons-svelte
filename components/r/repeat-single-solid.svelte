<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2p9unbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i2p9unbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:repeat-single-solid" {...props}></Icon>
