<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edghc2bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edghc2bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-display" {...props}></Icon>
