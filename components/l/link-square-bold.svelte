<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkgdzhhhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkgdzhhhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-square-bold" {...props}></Icon>
