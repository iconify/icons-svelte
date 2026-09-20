<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pryjc9bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pryjc9bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pause-circle-fill" {...props}></Icon>
