<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdrk0t4mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cdrk0t4mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fromkai-light" {...props}></Icon>
