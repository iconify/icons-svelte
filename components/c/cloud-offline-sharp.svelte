<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi1xcw0cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xi1xcw0cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-offline-sharp" {...props}></Icon>
