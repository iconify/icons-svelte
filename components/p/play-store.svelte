<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvw_whb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvw_whb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:play-store" {...props}></Icon>
