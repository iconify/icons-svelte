<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0ncd-w8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0ncd-w8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planarally-dark" {...props}></Icon>
