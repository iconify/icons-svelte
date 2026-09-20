<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqd9fbcab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mqd9fbcab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:coffee" {...props}></Icon>
