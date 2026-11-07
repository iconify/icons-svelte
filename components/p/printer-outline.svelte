<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihkre-bnx.css';
import '../../css/v/v7i0-vbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihkre-bnx"/><path clip-rule="evenodd" class="v7i0-vbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-outline" {...props}></Icon>
