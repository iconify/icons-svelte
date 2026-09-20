<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stlxi49ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stlxi49ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:artstation" {...props}></Icon>
