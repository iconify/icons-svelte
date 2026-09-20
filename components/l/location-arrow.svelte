<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3pvgtaya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3pvgtaya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:location-arrow" {...props}></Icon>
