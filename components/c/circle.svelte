<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5d42ccom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b5d42ccom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:circle" {...props}></Icon>
