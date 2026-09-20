<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxsg9ybrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxsg9ybrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:loops" {...props}></Icon>
