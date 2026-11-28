<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-78cp69d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-78cp69d primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:close-duotone" {...props}></Icon>
