<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk18vfb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uk18vfb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-tree" {...props}></Icon>
