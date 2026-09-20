<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgl8q109f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgl8q109f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reolink-light" {...props}></Icon>
