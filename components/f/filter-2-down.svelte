<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3g41gkfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3g41gkfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-down" {...props}></Icon>
