<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up2z56_ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up2z56_ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cratedb" {...props}></Icon>
