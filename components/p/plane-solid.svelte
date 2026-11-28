<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plna2dbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plna2dbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-solid" {...props}></Icon>
