<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/aap5atbkv.css';
import '../../css/s/s8-jh0bvg.css';
import '../../css/r/r4k-9nyuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="aap5atbkv"/><path class="s8-jh0bvg wm-a"/><path class="r4k-9nyuf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mails" {...props}></Icon>
