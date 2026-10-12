<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-os2b_i.css';
import '../../css/z/zyzgsactv.css';
import '../../css/c/c_vkhxzzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xg-os2b_i"/><path class="zyzgsactv"/><path class="c_vkhxzzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paste-20" {...props}></Icon>
