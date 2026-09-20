<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqkw6gb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqkw6gb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:document-location-filled" {...props}></Icon>
