<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svqoymb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svqoymb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-x-filled" {...props}></Icon>
