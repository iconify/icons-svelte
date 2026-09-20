<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1266b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr1266b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-circle-bold" {...props}></Icon>
