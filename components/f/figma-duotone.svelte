<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmdm1lbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmdm1lbdc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:figma-duotone" {...props}></Icon>
