<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4t9qmbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4t9qmbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-import" {...props}></Icon>
