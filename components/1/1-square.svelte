<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2-zhbbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="n2-zhbbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:1-square" {...props}></Icon>
