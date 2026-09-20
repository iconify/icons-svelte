<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qll5a5f5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qll5a5f5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komga-light" {...props}></Icon>
