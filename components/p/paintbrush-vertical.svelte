<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4fmgd0rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4fmgd0rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:paintbrush-vertical" {...props}></Icon>
