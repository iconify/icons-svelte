<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcklqbs9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcklqbs9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-minus-solid" {...props}></Icon>
