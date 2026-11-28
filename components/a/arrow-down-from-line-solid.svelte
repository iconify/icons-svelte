<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8j94bzho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8j94bzho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-from-line-solid" {...props}></Icon>
