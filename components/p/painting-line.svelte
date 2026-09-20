<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkr9t4bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkr9t4bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:painting-line" {...props}></Icon>
