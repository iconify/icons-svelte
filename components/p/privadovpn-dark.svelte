<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ucif9jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5ucif9jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privadovpn-dark" {...props}></Icon>
