<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khu7syn1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="khu7syn1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emergency" {...props}></Icon>
