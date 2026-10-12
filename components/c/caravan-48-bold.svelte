<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-x57btp.css';
import '../../css/b/b2241hbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yx-x57btp"/><path class="b2241hbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caravan-48-bold" {...props}></Icon>
