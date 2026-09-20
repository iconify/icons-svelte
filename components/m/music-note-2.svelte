<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egd6s5b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egd6s5b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:music-note-2" {...props}></Icon>
