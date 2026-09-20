<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdg-5zbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdg-5zbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flickr" {...props}></Icon>
