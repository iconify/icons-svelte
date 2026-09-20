<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz1bfel1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz1bfel1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-forbid-line" {...props}></Icon>
