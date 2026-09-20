<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am09x4voc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am09x4voc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:new-folder-fill" {...props}></Icon>
