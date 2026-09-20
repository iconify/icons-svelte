<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uve726r2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uve726r2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nasa" {...props}></Icon>
