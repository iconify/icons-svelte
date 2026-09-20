<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc5kqobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc5kqobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-hangouts-meet-logo-solid" {...props}></Icon>
