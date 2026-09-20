<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhh05tb7v.css';
import '../../css/a/ayxx-hbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhh05tb7v"/><path class="ayxx-hbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:door-line" {...props}></Icon>
