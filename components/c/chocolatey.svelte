<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lghfdm1ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lghfdm1ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chocolatey" {...props}></Icon>
