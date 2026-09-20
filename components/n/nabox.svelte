<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgyn-qbco.css';
import '../../css/i/i700k7_wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgyn-qbco"/><path clip-rule="evenodd" class="i700k7_wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nabox" {...props}></Icon>
