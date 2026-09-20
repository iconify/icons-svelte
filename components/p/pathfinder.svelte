<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol16gcbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol16gcbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pathfinder" {...props}></Icon>
