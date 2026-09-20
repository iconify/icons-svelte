<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wykzzvp4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wykzzvp4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-pdf-2-fill" {...props}></Icon>
