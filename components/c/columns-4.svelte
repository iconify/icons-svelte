<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6_06_per.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6_06_per"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns-4" {...props}></Icon>
