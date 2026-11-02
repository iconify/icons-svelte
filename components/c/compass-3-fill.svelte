<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-qd1dri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-qd1dri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-3-fill" {...props}></Icon>
