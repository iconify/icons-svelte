<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2f2hvbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="k2f2hvbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:k-square" {...props}></Icon>
