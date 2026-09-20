<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m02shab3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m02shab3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookhaven-dark" {...props}></Icon>
