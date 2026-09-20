<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr5lk82zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zr5lk82zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:film" {...props}></Icon>
