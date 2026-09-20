<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwdw506lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mwdw506lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:mountain-range" {...props}></Icon>
