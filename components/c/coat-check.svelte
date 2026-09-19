<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5m1j1b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5m1j1b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:coat-check" {...props}></Icon>
