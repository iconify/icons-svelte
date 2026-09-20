<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aniu8tw4w.css';
import '../../css/s/sw-wadboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aniu8tw4w"/><path class="sw-wadboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-setting-filled" {...props}></Icon>
