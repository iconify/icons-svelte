<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic9xufl-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic9xufl-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:msn-messenger-logo-solid" {...props}></Icon>
