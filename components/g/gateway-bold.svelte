<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpavn5bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpavn5bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gateway-bold" {...props}></Icon>
