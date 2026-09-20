<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-99oa8q.css';
import '../../css/m/m7s4zt-mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-99oa8q"/><path class="m7s4zt-mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-json-filled" {...props}></Icon>
