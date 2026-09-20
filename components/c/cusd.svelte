<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksd2czex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lksd2czex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cusd" {...props}></Icon>
