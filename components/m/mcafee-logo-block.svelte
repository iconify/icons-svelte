<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waskz5cwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="waskz5cwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mcafee-logo-block" {...props}></Icon>
