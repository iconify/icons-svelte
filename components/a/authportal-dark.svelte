<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgs82ubbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgs82ubbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authportal-dark" {...props}></Icon>
