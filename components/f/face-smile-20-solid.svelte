<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytv0zmnmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ytv0zmnmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:face-smile-20-solid" {...props}></Icon>
