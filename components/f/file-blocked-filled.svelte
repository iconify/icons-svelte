<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql3-6mw4a.css';
import '../../css/y/y81vbnbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3-6mw4a"/><path class="y81vbnbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-blocked-filled" {...props}></Icon>
