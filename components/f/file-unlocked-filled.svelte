<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgf_iypbv.css';
import '../../css/n/n662dbbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgf_iypbv"/><path class="n662dbbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-unlocked-filled" {...props}></Icon>
