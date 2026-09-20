<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy-ckacit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy-ckacit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:goldman-sachs" {...props}></Icon>
