<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7blleqsn.css';
import '../../css/u/uj_xhacmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7blleqsn"/><path class="uj_xhacmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:go-pro-bold" {...props}></Icon>
