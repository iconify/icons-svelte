<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8e9ro_ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h8e9ro_ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bus-front-fill" {...props}></Icon>
