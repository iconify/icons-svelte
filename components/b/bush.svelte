<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovbrx1qav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ovbrx1qav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bush" {...props}></Icon>
