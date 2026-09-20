<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eezro2b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eezro2b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-right" {...props}></Icon>
