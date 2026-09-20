<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk1t647en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sk1t647en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chest-fill" {...props}></Icon>
