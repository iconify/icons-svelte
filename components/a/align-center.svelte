<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sul6zry_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sul6zry_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:align-center" {...props}></Icon>
