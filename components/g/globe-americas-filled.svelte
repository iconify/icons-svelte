<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0m4k5a2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0m4k5a2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-americas-filled" {...props}></Icon>
