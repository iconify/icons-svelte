<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erh4ajb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erh4ajb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:global-off-fill" {...props}></Icon>
