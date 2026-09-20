<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n34ilnkrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n34ilnkrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flag-o" {...props}></Icon>
