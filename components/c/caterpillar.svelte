<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyav9cdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxyav9cdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:caterpillar" {...props}></Icon>
