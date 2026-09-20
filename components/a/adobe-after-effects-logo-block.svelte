<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpxl7f8fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zpxl7f8fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-after-effects-logo-block" {...props}></Icon>
