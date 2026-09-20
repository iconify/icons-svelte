<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wstd-w0xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wstd-w0xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:angular-logo-solid" {...props}></Icon>
