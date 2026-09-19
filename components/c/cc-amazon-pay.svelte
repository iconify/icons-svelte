<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg9anbbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bg9anbbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-amazon-pay" {...props}></Icon>
