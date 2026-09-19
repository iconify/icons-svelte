<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8iq1nhqs.css';
import '../../css/u/upas56-sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8iq1nhqs"/><path class="upas56-sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-edit" {...props}></Icon>
