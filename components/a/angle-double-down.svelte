<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf2tv_b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2tv_b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:angle-double-down" {...props}></Icon>
