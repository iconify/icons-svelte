<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtkn67b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtkn67b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:icx" {...props}></Icon>
