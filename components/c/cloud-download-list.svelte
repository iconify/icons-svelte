<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-v6niwrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m-v6niwrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-download-list" {...props}></Icon>
