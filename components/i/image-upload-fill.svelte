<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8-qsi84q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8-qsi84q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-upload-fill" {...props}></Icon>
