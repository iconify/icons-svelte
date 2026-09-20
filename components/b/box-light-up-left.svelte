<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyi5-4gvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pyi5-4gvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-left" {...props}></Icon>
