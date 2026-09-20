<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0u7fpb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0u7fpb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qlty" {...props}></Icon>
