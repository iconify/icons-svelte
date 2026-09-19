<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_bozcl2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b_bozcl2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:menu2" {...props}></Icon>
