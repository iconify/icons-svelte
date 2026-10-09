<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y69yz0bvp.css';
import '../../css/b/b9tupzbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y69yz0bvp"/><path class="b9tupzbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-20" {...props}></Icon>
