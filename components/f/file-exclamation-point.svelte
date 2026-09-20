<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c59ji3bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c59ji3bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-exclamation-point" {...props}></Icon>
