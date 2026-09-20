<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrk48pbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrk48pbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:movistar" {...props}></Icon>
