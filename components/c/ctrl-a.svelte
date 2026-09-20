<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlvh1icjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qlvh1icjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ctrl-a" {...props}></Icon>
