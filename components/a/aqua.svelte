<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhzgwmb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhzgwmb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aqua" {...props}></Icon>
