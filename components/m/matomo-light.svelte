<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv_niqbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sv_niqbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matomo-light" {...props}></Icon>
