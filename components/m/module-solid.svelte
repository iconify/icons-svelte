<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdqr4db0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdqr4db0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:module-solid" {...props}></Icon>
