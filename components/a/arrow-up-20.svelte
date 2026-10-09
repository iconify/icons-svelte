<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfzmnvd-w.css';
import '../../css/k/kz8f7vbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lfzmnvd-w"/><path class="kz8f7vbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-20" {...props}></Icon>
