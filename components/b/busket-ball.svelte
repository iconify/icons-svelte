<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow1xktbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="ow1xktbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:busket-ball" {...props}></Icon>
