<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0t27pb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0t27pb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reverbnation" {...props}></Icon>
