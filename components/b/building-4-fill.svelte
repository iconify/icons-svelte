<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ennsrvbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ennsrvbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:building-4-fill" {...props}></Icon>
