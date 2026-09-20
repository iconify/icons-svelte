<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im79o4bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im79o4bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:guitar-fill" {...props}></Icon>
