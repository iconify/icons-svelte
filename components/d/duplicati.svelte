<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp5n-8bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp5n-8bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:duplicati" {...props}></Icon>
