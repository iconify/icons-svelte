<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymj5zhe8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ymj5zhe8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow" {...props}></Icon>
