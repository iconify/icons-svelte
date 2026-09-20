<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4dmnlnbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o4dmnlnbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:grid-v" {...props}></Icon>
