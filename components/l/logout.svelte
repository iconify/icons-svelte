<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmvf2-mgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gmvf2-mgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:logout" {...props}></Icon>
