<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwldzvb5c.css';
import '../../css/s/spys-wb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="rwldzvb5c"/><path class="spys-wb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:first-aid-alt" {...props}></Icon>
