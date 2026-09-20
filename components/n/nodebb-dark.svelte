<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q30f-ac4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q30f-ac4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodebb-dark" {...props}></Icon>
