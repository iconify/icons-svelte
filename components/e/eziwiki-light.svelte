<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9a0a3bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9a0a3bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eziwiki-light" {...props}></Icon>
