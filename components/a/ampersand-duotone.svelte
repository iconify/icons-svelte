<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muybcsb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muybcsb3d primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ampersand-duotone" {...props}></Icon>
