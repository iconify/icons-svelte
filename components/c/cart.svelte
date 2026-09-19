<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9fsr8nug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9fsr8nug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:cart" {...props}></Icon>
