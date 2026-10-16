<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u49bxgz.css';
import '../../css/n/n-rap1bom.css';
import '../../css/e/ehybfubeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n5u49bxgz"/><path class="n-rap1bom"/><path class="ehybfubeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hinge-20-bold" {...props}></Icon>
