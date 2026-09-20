<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5bb0i2_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5bb0i2_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunasea-dark" {...props}></Icon>
