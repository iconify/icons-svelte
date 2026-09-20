<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7akl_s-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7akl_s-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-star" {...props}></Icon>
