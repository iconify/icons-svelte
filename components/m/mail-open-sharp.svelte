<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-1cb3qmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-1cb3qmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail-open-sharp" {...props}></Icon>
