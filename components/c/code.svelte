<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg8r48zoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dg8r48zoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:code" {...props}></Icon>
