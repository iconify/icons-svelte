<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6huerbpx.css';
import '../../css/l/li94czbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b6huerbpx"/><path class="li94czbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:level-gauge-20" {...props}></Icon>
