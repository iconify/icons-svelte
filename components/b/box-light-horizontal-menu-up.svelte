<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm42jgy4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zm42jgy4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-menu-up" {...props}></Icon>
