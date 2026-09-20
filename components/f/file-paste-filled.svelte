<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntpi8xe8d.css';
import '../../css/z/z_klffbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntpi8xe8d"/><path class="z_klffbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-paste-filled" {...props}></Icon>
