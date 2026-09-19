<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax6hhubxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6hhubxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:instagram" {...props}></Icon>
