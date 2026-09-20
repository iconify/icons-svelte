<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4im118es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z4im118es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:anchor" {...props}></Icon>
