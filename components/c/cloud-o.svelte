<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9z9i0-vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9z9i0-vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cloud-o" {...props}></Icon>
