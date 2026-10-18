<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yifcz_b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yifcz_b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-4" {...props}></Icon>
