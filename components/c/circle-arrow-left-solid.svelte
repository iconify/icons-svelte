<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5zx90bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5zx90bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-left-solid" {...props}></Icon>
