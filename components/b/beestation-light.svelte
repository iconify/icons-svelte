<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfiofnb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dfiofnb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beestation-light" {...props}></Icon>
