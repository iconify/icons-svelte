<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_s0tzwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fp_s0tzwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-off-solid" {...props}></Icon>
