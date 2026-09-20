<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqx6e0bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqx6e0bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-star-fill" {...props}></Icon>
