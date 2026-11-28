<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzv-gcbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzv-gcbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:playlist-refresh" {...props}></Icon>
