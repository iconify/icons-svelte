<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey5jcwb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey5jcwb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gitlab" {...props}></Icon>
