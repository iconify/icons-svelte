<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv7kf4u0i.css';
import '../../css/j/j79w86gjb.css';
import '../../css/i/i2oj4_bht.css';
import '../../css/d/dtjo7_p7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sv7kf4u0i wm-a"/><path class="j79w86gjb wm-a"/><path class="i2oj4_bht wm-a"/><path class="dtjo7_p7q wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:audio-lines" {...props}></Icon>
