<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0d7aqnpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0d7aqnpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autocaliweb-dark" {...props}></Icon>
