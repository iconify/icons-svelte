<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu_d9ibfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lu_d9ibfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coal-48-bold" {...props}></Icon>
