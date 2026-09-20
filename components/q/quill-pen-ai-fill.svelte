<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk0gxtbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk0gxtbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:quill-pen-ai-fill" {...props}></Icon>
