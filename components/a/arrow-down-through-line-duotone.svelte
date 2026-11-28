<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkz3gtb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkz3gtb6d primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-through-line-duotone" {...props}></Icon>
