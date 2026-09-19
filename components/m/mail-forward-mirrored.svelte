<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7_gw7lhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q7_gw7lhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-forward-mirrored" {...props}></Icon>
