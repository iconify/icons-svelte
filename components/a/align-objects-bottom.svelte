<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1s550b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1s550b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-objects-bottom" {...props}></Icon>
