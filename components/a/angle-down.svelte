<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcs96yn7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zcs96yn7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-down" {...props}></Icon>
