<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3w_t7krg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l3w_t7krg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:clock" {...props}></Icon>
