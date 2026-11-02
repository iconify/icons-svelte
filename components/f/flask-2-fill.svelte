<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj2lqzbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj2lqzbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-2-fill" {...props}></Icon>
