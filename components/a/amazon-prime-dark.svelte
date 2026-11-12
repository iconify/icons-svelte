<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-u8tebtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-u8tebtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime-dark" {...props}></Icon>
