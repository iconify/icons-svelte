<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4v-c_q2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x4v-c_q2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-grid-20" {...props}></Icon>
