<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmog9oz3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bmog9oz3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hammer" {...props}></Icon>
