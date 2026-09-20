<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/totvf6b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="totvf6b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:dental-chair" {...props}></Icon>
