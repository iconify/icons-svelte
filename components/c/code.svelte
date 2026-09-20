<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw_q1lu_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_q1lu_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:code" {...props}></Icon>
