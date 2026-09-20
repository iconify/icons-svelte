<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3uh-pgdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p3uh-pgdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:archway" {...props}></Icon>
