<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kocj6_b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kocj6_b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:plugin-hands-puzzle" {...props}></Icon>
