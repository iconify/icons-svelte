<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhgf4oq2b.css';
import '../../css/l/lguu5_wzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhgf4oq2b"/><path class="lguu5_wzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-import-filled" {...props}></Icon>
