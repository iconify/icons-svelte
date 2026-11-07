<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52hq6b9u.css';
import '../../css/z/z9kgvgb1l.css';
import '../../css/w/wfiv04kcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h52hq6b9u"/><path class="z9kgvgb1l"/><path class="wfiv04kcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-off-outline" {...props}></Icon>
