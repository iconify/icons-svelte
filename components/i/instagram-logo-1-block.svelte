<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diko8da2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="diko8da2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instagram-logo-1-block" {...props}></Icon>
