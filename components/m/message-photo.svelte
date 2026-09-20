<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8c-64bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8c-64bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:message-photo" {...props}></Icon>
