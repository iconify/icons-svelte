<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2_r3-b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2_r3-b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:database-safety" {...props}></Icon>
