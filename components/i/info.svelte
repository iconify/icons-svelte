<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkd_uccph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":24};
const content = `<path class="pkd_uccph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:info" {...props}></Icon>
