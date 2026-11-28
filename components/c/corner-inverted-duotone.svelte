<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh4qecb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary uh4qecb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-inverted-duotone" {...props}></Icon>
