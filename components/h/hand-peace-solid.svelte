<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3nipccuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3nipccuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hand-peace-solid" {...props}></Icon>
