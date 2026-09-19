<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w--sykbuv.css';
import '../../css/i/ik2-15cxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w--sykbuv"/><path class="ik2-15cxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:behance-fill" {...props}></Icon>
