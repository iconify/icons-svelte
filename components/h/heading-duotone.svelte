<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikxjudb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikxjudb1a primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-duotone" {...props}></Icon>
