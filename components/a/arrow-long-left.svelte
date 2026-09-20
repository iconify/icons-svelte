<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm8tcc-lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xm8tcc-lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-long-left" {...props}></Icon>
