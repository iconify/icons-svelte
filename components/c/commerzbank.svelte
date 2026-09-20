<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0anb-bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0anb-bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:commerzbank" {...props}></Icon>
