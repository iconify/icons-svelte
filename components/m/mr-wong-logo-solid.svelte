<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix5upybjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ix5upybjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mr-wong-logo-solid" {...props}></Icon>
