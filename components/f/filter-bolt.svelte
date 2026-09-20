<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4crvgbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4crvgbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-bolt" {...props}></Icon>
