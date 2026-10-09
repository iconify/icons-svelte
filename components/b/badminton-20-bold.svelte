<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp8tavb-f.css';
import '../../css/v/vuh460n8o.css';
import '../../css/f/f78t3-62r.css';
import '../../css/r/r4kug05-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fp8tavb-f"/><path class="vuh460n8o"/><path class="f78t3-62r"/><path class="r4kug05-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badminton-20-bold" {...props}></Icon>
