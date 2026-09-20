<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1fb3obky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1fb3obky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deutsche-welle" {...props}></Icon>
