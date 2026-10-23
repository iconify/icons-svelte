<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfcc_jb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfcc_jb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grid-3x2" {...props}></Icon>
