<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi-ee_d_q.css';
import '../../css/i/i9aia1bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi-ee_d_q"/><path clip-rule="evenodd" class="i9aia1bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:expressjs" {...props}></Icon>
