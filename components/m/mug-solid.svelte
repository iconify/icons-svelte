<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6x6upbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6x6upbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mug-solid" {...props}></Icon>
