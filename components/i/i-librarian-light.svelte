<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkw3vswdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkw3vswdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:i-librarian-light" {...props}></Icon>
