<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtub--b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mtub--b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:plus-box-fill" {...props}></Icon>
