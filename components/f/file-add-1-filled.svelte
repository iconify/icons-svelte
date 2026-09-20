<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvr2fiwiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvr2fiwiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-add-1-filled" {...props}></Icon>
