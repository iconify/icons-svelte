<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp294gxeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp294gxeo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:more-horizontal-duotone" {...props}></Icon>
