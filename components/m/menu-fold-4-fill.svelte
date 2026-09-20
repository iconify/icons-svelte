<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9xwiybth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9xwiybth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-fold-4-fill" {...props}></Icon>
