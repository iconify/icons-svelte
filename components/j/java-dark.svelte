<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx9w5c09m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx9w5c09m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:java-dark" {...props}></Icon>
