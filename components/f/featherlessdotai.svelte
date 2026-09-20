<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtpxpob0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpxpob0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:featherlessdotai" {...props}></Icon>
