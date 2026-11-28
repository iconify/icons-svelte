<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_s4wsb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_s4wsb7p primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-off-duotone" {...props}></Icon>
