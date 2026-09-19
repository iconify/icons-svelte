<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yddqc0brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yddqc0brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:a-arrow-down" {...props}></Icon>
