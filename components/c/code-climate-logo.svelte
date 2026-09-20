<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi8iyxe_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8iyxe_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:code-climate-logo" {...props}></Icon>
