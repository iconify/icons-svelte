<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6er7-e_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6er7-e_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:phone-incoming" {...props}></Icon>
