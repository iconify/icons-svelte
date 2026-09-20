<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy-8mqb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy-8mqb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-rupee-circle-fill" {...props}></Icon>
