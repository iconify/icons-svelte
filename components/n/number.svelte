<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfseh4bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bfseh4bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:number" {...props}></Icon>
