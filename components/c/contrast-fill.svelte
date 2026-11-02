<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8q0hb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8q0hb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contrast-fill" {...props}></Icon>
