<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr3lh1bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr3lh1bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fusionauth-light" {...props}></Icon>
