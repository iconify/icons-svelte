<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u16dxc66j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u16dxc66j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:claris-logo-solid" {...props}></Icon>
