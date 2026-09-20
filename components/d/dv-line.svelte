<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bok3snb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bok3snb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dv-line" {...props}></Icon>
