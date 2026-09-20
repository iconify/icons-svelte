<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oku8xrlhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oku8xrlhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-bridge-logo-solid" {...props}></Icon>
