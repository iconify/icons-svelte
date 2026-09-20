<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r14uh_74t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r14uh_74t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-edit" {...props}></Icon>
