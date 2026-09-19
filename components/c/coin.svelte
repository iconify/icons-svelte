<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg5fzvb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5fzvb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coin" {...props}></Icon>
