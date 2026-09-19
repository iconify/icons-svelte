<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_e_t9pnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_e_t9pnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pulse" {...props}></Icon>
