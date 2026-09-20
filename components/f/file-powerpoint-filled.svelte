<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enwlp0z_q.css';
import '../../css/m/mz6j3r8mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enwlp0z_q"/><path class="mz6j3r8mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-powerpoint-filled" {...props}></Icon>
