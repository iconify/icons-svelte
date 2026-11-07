<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhj7tk-5q.css';
import '../../css/c/cnl0-vb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path clip-rule="evenodd" class="cnl0-vb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-send-bold" {...props}></Icon>
