<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up_032bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up_032bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iwiw-logo-2-solid" {...props}></Icon>
