<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au1n8ebss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au1n8ebss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:link-unlink" {...props}></Icon>
