<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smd-g2-lg.css';
import '../../css/w/w9yumzbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smd-g2-lg"/><path clip-rule="evenodd" class="w9yumzbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bitcoin-circle-filled" {...props}></Icon>
