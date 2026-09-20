<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3imbrjdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="o3imbrjdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-fold-up-left" {...props}></Icon>
