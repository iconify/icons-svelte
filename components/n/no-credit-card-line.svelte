<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7pn4bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7pn4bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:no-credit-card-line" {...props}></Icon>
