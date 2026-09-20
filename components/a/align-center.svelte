<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k383-3bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k383-3bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:align-center" {...props}></Icon>
