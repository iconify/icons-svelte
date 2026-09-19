<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq36qjv9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq36qjv9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-paint" {...props}></Icon>
