<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de49-_pzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de49-_pzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:homarr" {...props}></Icon>
