<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxvnqabpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fxvnqabpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:account" {...props}></Icon>
