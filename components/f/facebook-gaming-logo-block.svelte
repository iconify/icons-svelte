<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czozas11e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czozas11e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-gaming-logo-block" {...props}></Icon>
