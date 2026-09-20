<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7b5ovbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y7b5ovbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flight-takeoff" {...props}></Icon>
