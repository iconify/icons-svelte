<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vd2w9_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="p9vd2w9_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:building" {...props}></Icon>
