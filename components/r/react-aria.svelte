<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbivy8bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":790,"left":200,"top":206};
const content = `<path class="sbivy8bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:react-aria" {...props}></Icon>
