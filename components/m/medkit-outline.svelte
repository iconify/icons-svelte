<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecffrn81e.css';
import '../../css/z/zzs6n-cer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ecffrn81e"/><path class="zzs6n-cer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:medkit-outline" {...props}></Icon>
