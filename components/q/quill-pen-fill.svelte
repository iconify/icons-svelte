<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-c4y4b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-c4y4b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quill-pen-fill" {...props}></Icon>
