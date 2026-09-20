<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toef6xbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toef6xbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:500px-logo-2-block" {...props}></Icon>
