<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu6tghbwj.css';
import '../../css/l/lb66l3jkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qu6tghbwj"/><path class="lb66l3jkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-sheets-light" {...props}></Icon>
