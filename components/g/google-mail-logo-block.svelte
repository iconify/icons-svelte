<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf8h-u92t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf8h-u92t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-mail-logo-block" {...props}></Icon>
