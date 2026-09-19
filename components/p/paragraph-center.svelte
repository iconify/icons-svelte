<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljxyob6qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ljxyob6qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paragraph-center" {...props}></Icon>
