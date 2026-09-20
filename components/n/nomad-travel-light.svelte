<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuwh--krg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuwh--krg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nomad-travel-light" {...props}></Icon>
