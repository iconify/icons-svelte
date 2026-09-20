<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyqzsr44f.css';
import '../../css/e/evgip2bmd.css';
import '../../css/e/e8wgpct6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gyqzsr44f"/><path class="evgip2bmd"/><path class="e8wgpct6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:css-map" {...props}></Icon>
