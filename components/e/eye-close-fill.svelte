<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt2w29brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt2w29brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-close-fill" {...props}></Icon>
