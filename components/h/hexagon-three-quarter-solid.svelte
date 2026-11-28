<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdo3n1bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdo3n1bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-three-quarter-solid" {...props}></Icon>
