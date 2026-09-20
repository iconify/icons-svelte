<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4lbmm.css';
import '../../css/y/ydovum.css';
import '../../css/t/tzu-tt.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4lbmm ydovum"/><path class="tzu-tt ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:paint-drop-half-filled-twotone" {...props}></Icon>
