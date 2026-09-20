<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayho2yb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayho2yb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:500px-logo-2-solid" {...props}></Icon>
