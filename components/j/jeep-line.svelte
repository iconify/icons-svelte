<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqp8m2bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqp8m2bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jeep-line" {...props}></Icon>
