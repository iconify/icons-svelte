<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyokz7bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gyokz7bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-download-list-filled" {...props}></Icon>
