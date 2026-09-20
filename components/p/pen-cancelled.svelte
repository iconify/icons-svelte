<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq8vz1bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gq8vz1bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pen-cancelled" {...props}></Icon>
