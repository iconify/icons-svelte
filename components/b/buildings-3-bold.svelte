<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf-ow3pxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf-ow3pxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-3-bold" {...props}></Icon>
