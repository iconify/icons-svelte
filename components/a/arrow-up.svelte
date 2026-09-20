<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atjsaccyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="atjsaccyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-up" {...props}></Icon>
