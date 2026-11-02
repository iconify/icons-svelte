<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psi_79vqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psi_79vqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:face-mask-line" {...props}></Icon>
