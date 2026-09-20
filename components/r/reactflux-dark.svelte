<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-j1wjl-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-j1wjl-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reactflux-dark" {...props}></Icon>
