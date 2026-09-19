<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix4609bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix4609bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:ellipsis" {...props}></Icon>
