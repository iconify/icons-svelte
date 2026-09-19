<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdgookbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1792};
const content = `<path class="kdgookbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mouse-pointer" {...props}></Icon>
