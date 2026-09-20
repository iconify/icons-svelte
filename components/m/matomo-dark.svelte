<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc794qb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc794qb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matomo-dark" {...props}></Icon>
