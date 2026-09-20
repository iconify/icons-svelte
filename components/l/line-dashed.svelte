<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1eig5b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="y1eig5b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line-dashed" {...props}></Icon>
