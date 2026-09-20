<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjmd_m1pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjmd_m1pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gdgt-logo-solid" {...props}></Icon>
