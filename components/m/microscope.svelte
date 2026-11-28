<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqce_m6so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqce_m6so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:microscope" {...props}></Icon>
