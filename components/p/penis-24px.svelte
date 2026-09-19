<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it7z-_d_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it7z-_d_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:penis-24px" {...props}></Icon>
