<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4kgskj6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o4kgskj6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:idaho" {...props}></Icon>
