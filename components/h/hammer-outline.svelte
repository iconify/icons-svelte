<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3dn06bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3dn06bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hammer-outline" {...props}></Icon>
