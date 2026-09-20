<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7tkv1bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n7tkv1bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:customer" {...props}></Icon>
