<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6sxug.css';
import '../../css/i/iw1iew.css';
import '../../css/r/r3cp3p.css';
import '../../css/s/so-to-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6sxug iw1iew"/><path class="iw1iew r3cp3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm-square-twotone-to-square-twotone-transition" {...props}></Icon>
