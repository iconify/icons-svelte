<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npnjj3bqi.css';
import '../../css/l/laen_wd4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npnjj3bqi"/><path class="laen_wd4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-top-up-outline" {...props}></Icon>
