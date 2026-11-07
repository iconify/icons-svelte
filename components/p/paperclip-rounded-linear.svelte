<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqben4olh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqben4olh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-rounded-linear" {...props}></Icon>
