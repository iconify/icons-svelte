<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av3ar4-9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av3ar4-9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-export-fill" {...props}></Icon>
