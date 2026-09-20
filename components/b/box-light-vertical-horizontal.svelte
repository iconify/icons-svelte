<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-fv5ok9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c-fv5ok9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal" {...props}></Icon>
