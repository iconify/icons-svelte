<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2xw--bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2xw--bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cake-2-fill" {...props}></Icon>
