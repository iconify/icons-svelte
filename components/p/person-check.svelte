<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxl3s1f2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxl3s1f2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:person-check" {...props}></Icon>
