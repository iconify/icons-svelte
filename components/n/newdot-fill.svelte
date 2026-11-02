<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw94qbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdw94qbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:newdot-fill" {...props}></Icon>
