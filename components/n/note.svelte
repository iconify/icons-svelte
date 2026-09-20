<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxky71b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxky71b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:note" {...props}></Icon>
