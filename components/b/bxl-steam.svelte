<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lve74zb5j.css';
import '../../css/r/rkbyxzbvs.css';
import '../../css/h/hxxjcny9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lve74zb5j"/><path class="rkbyxzbvs"/><path class="hxxjcny9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-steam" {...props}></Icon>
