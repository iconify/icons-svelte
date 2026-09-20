<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_q25gb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_q25gb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ellipsis-h" {...props}></Icon>
