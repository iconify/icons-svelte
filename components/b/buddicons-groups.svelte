<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn5v98bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gn5v98bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-groups" {...props}></Icon>
