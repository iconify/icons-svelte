<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyf0oqb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyf0oqb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:adobe" {...props}></Icon>
