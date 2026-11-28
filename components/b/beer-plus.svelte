<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixr5k-b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixr5k-b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:beer-plus" {...props}></Icon>
