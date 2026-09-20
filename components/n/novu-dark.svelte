<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtyemfz0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mtyemfz0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:novu-dark" {...props}></Icon>
