<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/harom8_fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="harom8_fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-video-fill" {...props}></Icon>
