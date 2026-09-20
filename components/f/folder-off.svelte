<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmln_jmlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmln_jmlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-off" {...props}></Icon>
