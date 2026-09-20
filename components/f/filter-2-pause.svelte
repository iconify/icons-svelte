<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyqe-6bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyqe-6bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-pause" {...props}></Icon>
