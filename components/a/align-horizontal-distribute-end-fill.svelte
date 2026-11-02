<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_-lpel1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_-lpel1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-distribute-end-fill" {...props}></Icon>
