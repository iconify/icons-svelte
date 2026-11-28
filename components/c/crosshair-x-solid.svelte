<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1gywdbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1gywdbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:crosshair-x-solid" {...props}></Icon>
