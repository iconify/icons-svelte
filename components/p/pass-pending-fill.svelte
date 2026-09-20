<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uegkk1bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uegkk1bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pass-pending-fill" {...props}></Icon>
