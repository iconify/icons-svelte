<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1n2s360d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1n2s360d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hp" {...props}></Icon>
