<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjgys6ave.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjgys6ave"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clubs-filled" {...props}></Icon>
