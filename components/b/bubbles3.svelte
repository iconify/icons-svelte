<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz-_py4dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="pz-_py4dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bubbles3" {...props}></Icon>
