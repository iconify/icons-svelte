<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pym99p-_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pym99p-_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:premier-league" {...props}></Icon>
