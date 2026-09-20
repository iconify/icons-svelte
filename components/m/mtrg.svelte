<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx2t3vb9s.css';
import '../../css/q/qr0d49tfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2t3vb9s"/><path class="qr0d49tfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mtrg" {...props}></Icon>
