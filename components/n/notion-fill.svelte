<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw_-10c8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_-10c8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notion-fill" {...props}></Icon>
