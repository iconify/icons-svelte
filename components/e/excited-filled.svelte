<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrmky_bdh.css';
import '../../css/z/zos2k5b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrmky_bdh"/><path class="zos2k5b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:excited-filled" {...props}></Icon>
