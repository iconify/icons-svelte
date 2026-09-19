<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn6ppjb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn6ppjb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bebo" {...props}></Icon>
