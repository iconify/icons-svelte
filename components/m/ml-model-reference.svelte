<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtnvolzvt.css';
import '../../css/x/xd2sz9b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mtnvolzvt"/><path class="xd2sz9b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ml-model-reference" {...props}></Icon>
