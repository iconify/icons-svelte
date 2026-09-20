<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qodb1q9bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qodb1q9bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-left-click" {...props}></Icon>
