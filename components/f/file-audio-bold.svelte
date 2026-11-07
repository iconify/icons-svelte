<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv_p3kcsw.css';
import '../../css/w/w6x-4ipkl.css';
import '../../css/x/x8_a0bb_i.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv_p3kcsw"/><path class="w6x-4ipkl"/><path clip-rule="evenodd" class="x8_a0bb_i"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-audio-bold" {...props}></Icon>
