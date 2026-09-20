<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5u3m-8_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5u3m-8_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunar-dark" {...props}></Icon>
