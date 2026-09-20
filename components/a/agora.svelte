<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml94e4_dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml94e4_dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:agora" {...props}></Icon>
