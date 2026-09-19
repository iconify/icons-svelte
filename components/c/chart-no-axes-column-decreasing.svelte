<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fppphsa7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fppphsa7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-no-axes-column-decreasing" {...props}></Icon>
