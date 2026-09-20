<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4uxtx7ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4uxtx7ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adnanh-webhook-dark" {...props}></Icon>
