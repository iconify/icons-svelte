<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_ilgq-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b_ilgq-0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:indent-decrease" {...props}></Icon>
