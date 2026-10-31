<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvdndccrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvdndccrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-minus-corner-fill-round" {...props}></Icon>
