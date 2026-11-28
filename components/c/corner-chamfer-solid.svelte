<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyfr0tjbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyfr0tjbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-chamfer-solid" {...props}></Icon>
