<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up2mkyrhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up2mkyrhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:obtainium" {...props}></Icon>
