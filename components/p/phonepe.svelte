<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrt8iwbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrt8iwbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:phonepe" {...props}></Icon>
