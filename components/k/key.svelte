<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ki49b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9ki49b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:key" {...props}></Icon>
