<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy5wuebdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5wuebdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layout-dashboard-sharp" {...props}></Icon>
