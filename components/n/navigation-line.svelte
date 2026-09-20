<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvy203q6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvy203q6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:navigation-line" {...props}></Icon>
