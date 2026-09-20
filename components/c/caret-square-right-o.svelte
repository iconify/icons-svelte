<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cflr1ab0i.css';
import '../../css/u/uu2hu__dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cflr1ab0i"/><path class="uu2hu__dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:caret-square-right-o" {...props}></Icon>
