<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzc-u03if.css';
import '../../css/a/a7qi5pmcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzc-u03if"/><path class="a7qi5pmcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-heart-bold-duotone" {...props}></Icon>
