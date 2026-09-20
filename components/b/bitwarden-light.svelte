<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qji0dibyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qji0dibyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitwarden-light" {...props}></Icon>
