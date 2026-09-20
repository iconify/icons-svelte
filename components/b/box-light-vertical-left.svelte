<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h47jajpue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h47jajpue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-left" {...props}></Icon>
