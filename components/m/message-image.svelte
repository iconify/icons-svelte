<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwg6rltna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwg6rltna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:message-image" {...props}></Icon>
