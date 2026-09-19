<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcbtzpi5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcbtzpi5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flask" {...props}></Icon>
