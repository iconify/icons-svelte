<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsaiwdb4t.css';
import '../../css/b/bwry4rblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsaiwdb4t"/><path class="bwry4rblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dining-48" {...props}></Icon>
