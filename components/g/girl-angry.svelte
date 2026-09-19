<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urmq5bc6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urmq5bc6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-angry" {...props}></Icon>
