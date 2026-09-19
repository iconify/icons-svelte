<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsiui4qwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsiui4qwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-right-stroke" {...props}></Icon>
