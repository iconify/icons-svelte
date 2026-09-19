<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pojn_z1wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pojn_z1wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:report-hacked" {...props}></Icon>
