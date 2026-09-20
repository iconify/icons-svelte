<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekufx7jer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ekufx7jer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:align-right" {...props}></Icon>
