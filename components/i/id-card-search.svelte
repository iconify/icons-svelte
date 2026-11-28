<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga2uribhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga2uribhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:id-card-search" {...props}></Icon>
