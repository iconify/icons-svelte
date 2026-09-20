<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqvxq3bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqvxq3bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:contrast-1-filled" {...props}></Icon>
