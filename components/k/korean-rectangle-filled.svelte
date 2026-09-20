<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpb0-dwzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpb0-dwzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:korean-rectangle-filled" {...props}></Icon>
