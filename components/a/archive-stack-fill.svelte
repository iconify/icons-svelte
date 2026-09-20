<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itj2tfnbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itj2tfnbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:archive-stack-fill" {...props}></Icon>
