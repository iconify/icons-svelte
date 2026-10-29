<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ql1hubg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ql1hubg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-2-solid" {...props}></Icon>
