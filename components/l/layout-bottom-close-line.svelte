<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs02mwb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs02mwb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-close-line" {...props}></Icon>
