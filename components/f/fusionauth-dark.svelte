<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2uz52m7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2uz52m7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fusionauth-dark" {...props}></Icon>
