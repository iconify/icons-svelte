<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swwt4xbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swwt4xbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fsharp" {...props}></Icon>
