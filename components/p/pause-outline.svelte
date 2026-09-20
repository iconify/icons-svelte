<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6kdxppgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q6kdxppgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pause-outline" {...props}></Icon>
