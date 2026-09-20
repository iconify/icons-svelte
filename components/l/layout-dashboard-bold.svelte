<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vby78g3_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vby78g3_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:layout-dashboard-bold" {...props}></Icon>
