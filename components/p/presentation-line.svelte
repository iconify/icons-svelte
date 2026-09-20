<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq3zkbbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq3zkbbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:presentation-line" {...props}></Icon>
