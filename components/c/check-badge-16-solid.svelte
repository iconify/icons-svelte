<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdf_o1auv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fdf_o1auv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-badge-16-solid" {...props}></Icon>
