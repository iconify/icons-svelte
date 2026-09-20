<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s16yy-ilo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s16yy-ilo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:insert-cloud-video-solid" {...props}></Icon>
