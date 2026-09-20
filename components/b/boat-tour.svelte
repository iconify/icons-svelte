<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtdiujbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="qtdiujbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat-tour" {...props}></Icon>
