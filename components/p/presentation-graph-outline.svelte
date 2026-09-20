<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edm1jx-qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edm1jx-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:presentation-graph-outline" {...props}></Icon>
