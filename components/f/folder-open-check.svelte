<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai_m1zzqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai_m1zzqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-open-check" {...props}></Icon>
