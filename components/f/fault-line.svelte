<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upi7cjb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upi7cjb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fault-line" {...props}></Icon>
