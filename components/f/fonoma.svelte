<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgt19h77j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgt19h77j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fonoma" {...props}></Icon>
