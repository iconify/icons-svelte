<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofm3hvbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ofm3hvbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-open-2-fill" {...props}></Icon>
