<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skdtm7eru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="skdtm7eru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:paved-road-alt2x-outline" {...props}></Icon>
