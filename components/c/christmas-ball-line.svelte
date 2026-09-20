<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmtgx5unr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmtgx5unr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christmas-ball-line" {...props}></Icon>
