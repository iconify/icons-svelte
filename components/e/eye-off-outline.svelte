<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urtzmgbhs.css';
import '../../css/q/q5rhorqnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urtzmgbhs"/><path class="q5rhorqnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:eye-off-outline" {...props}></Icon>
