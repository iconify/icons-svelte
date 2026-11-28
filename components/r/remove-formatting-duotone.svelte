<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myq6b2b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myq6b2b0h primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:remove-formatting-duotone" {...props}></Icon>
