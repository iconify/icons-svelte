<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f87ux6bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f87ux6bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bill-4-solid" {...props}></Icon>
