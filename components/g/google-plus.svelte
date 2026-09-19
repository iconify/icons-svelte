<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgaodkjyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgaodkjyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:google-plus" {...props}></Icon>
