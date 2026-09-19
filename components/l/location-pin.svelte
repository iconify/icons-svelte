<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af6zf9bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af6zf9bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:location-pin" {...props}></Icon>
