<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwxk4rnkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwxk4rnkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:convos" {...props}></Icon>
