<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbwxpt-wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tbwxpt-wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-network" {...props}></Icon>
