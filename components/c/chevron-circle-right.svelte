<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grwh7o55x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="grwh7o55x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-circle-right" {...props}></Icon>
