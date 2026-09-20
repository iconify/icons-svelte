<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sicp8y6ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sicp8y6ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bohemia-interactive" {...props}></Icon>
