<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0cjbbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bb0cjbbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:rocket" {...props}></Icon>
