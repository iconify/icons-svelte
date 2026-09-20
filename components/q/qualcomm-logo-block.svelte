<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svgzmibnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svgzmibnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:qualcomm-logo-block" {...props}></Icon>
