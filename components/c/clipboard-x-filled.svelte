<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l17hfdciu.css';
import '../../css/d/dtwl1wjmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l17hfdciu"/><path class="dtwl1wjmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clipboard-x-filled" {...props}></Icon>
