<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pau5rcb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pau5rcb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plant-wilt" {...props}></Icon>
