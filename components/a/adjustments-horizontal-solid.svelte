<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_7hgk3tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_7hgk3tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-horizontal-solid" {...props}></Icon>
