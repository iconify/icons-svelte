<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up3gczb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up3gczb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:flickr-logo-solid" {...props}></Icon>
