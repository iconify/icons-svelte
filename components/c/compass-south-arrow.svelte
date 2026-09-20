<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjptze3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yjptze3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-south-arrow" {...props}></Icon>
