<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_qksxbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h_qksxbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pencil-20-solid" {...props}></Icon>
