<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urysg1b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="urysg1b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:doctor-briefcase" {...props}></Icon>
