<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_fm6bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk_fm6bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:faceid-fill" {...props}></Icon>
