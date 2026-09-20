<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl2nwrbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2nwrbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-3" {...props}></Icon>
