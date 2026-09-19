<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md2u8j46v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md2u8j46v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-sharp" {...props}></Icon>
