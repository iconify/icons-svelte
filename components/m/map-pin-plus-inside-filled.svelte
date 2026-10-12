<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1h1xacii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1h1xacii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-plus-inside-filled" {...props}></Icon>
