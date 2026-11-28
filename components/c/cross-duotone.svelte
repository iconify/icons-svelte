<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fele_wbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fele_wbis primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cross-duotone" {...props}></Icon>
