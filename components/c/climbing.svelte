<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vko84lncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vko84lncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:climbing" {...props}></Icon>
