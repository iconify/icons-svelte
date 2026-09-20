<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe7x_gb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe7x_gb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intelowl-dark" {...props}></Icon>
