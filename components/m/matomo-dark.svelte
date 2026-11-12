<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqs10by8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yqs10by8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matomo-dark" {...props}></Icon>
