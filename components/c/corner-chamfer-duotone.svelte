<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4kc1e1el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4kc1e1el primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-chamfer-duotone" {...props}></Icon>
