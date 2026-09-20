<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lblsu7bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lblsu7bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kiwix" {...props}></Icon>
