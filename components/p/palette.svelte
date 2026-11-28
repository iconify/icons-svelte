<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fux6-slpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fux6-slpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:palette" {...props}></Icon>
