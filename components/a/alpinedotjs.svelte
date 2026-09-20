<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2y8yhbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2y8yhbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alpinedotjs" {...props}></Icon>
