<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ist_axrux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ist_axrux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-video" {...props}></Icon>
