<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og56l8bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og56l8bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ambulance-clock" {...props}></Icon>
