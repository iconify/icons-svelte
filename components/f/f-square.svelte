<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmpahqb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="cmpahqb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:f-square" {...props}></Icon>
