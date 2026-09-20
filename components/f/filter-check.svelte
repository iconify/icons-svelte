<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-s5j9brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-s5j9brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-check" {...props}></Icon>
