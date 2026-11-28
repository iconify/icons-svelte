<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sequ2mpmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sequ2mpmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:golf-solid" {...props}></Icon>
