<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq5knvfps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq5knvfps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-box-fill" {...props}></Icon>
