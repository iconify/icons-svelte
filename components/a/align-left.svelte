<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyeo_epso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyeo_epso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:align-left" {...props}></Icon>
