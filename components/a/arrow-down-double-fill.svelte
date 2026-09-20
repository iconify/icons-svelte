<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7869lbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7869lbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-double-fill" {...props}></Icon>
