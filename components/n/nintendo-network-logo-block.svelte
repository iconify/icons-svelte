<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7y4vubxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7y4vubxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nintendo-network-logo-block" {...props}></Icon>
