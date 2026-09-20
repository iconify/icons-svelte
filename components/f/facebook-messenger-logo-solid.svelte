<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhevecb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhevecb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-messenger-logo-solid" {...props}></Icon>
