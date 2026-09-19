<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trhuiyb4d.css';
import '../../css/j/j_4gibdnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trhuiyb4d"/><path class="j_4gibdnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:edit" {...props}></Icon>
