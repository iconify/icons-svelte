<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxxghkvqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zxxghkvqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:arrow-forward" {...props}></Icon>
