<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej3j5_fhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej3j5_fhc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-off-page-duotone" {...props}></Icon>
