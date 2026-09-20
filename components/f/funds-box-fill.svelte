<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auy9bfb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auy9bfb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:funds-box-fill" {...props}></Icon>
