<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf9o9n5rb.css';
import '../../css/k/kpz-x8bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf9o9n5rb"/><path clip-rule="evenodd" class="kpz-x8bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bedside-table-2-outline" {...props}></Icon>
