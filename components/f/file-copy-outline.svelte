<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1ivvrl4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ivvrl4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-copy-outline" {...props}></Icon>
