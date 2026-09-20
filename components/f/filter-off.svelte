<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii5fitmfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii5fitmfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-off" {...props}></Icon>
