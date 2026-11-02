<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihk2tf_ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihk2tf_ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:iteration-ccw-fill" {...props}></Icon>
