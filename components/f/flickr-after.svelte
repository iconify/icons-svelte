<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7mo3xirp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="c7mo3xirp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flickr-after" {...props}></Icon>
