<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek3k3cbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek3k3cbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:airplane" {...props}></Icon>
