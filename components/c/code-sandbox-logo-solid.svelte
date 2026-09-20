<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg0lr7rfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg0lr7rfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:code-sandbox-logo-solid" {...props}></Icon>
