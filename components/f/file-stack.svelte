<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m58c5-3dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m58c5-3dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-stack" {...props}></Icon>
