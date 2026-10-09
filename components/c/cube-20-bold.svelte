<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yozhcqskc.css';
import '../../css/t/tkfpxusan.css';
import '../../css/y/y9re-u6qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yozhcqskc"/><path class="tkfpxusan"/><path class="y9re-u6qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cube-20-bold" {...props}></Icon>
